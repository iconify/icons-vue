<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgb7w0bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgb7w0bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:city-13-filled" /></template>
