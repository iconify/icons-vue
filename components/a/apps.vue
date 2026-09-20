<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b63jx1bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b63jx1bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:apps" /></template>
