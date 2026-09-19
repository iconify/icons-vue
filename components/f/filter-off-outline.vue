<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyi3rac9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyi3rac9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:filter-off-outline" /></template>
