<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cze7y0brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cze7y0brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:cake-filled" /></template>
