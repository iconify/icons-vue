<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx8yl6bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nx8yl6bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:blogger" /></template>
