<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtvil53gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtvil53gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heading-duotone" /></template>
