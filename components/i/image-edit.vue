<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r698tjbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r698tjbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:image-edit" /></template>
