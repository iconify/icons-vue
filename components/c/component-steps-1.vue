<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gga6pngkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gga6pngkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:component-steps-1" /></template>
