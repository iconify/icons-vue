<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov6z5xbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov6z5xbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:clipboard-list-solid" /></template>
