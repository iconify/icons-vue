<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaryj4bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zaryj4bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:eject" /></template>
