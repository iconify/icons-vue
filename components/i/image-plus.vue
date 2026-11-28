<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycr5y2skk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycr5y2skk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:image-plus" /></template>
