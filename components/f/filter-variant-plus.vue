<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b84wse9vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b84wse9vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:filter-variant-plus" /></template>
