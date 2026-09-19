<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur3vd-8dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur3vd-8dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:do-redo-thin" /></template>
