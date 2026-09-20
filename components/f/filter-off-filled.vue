<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zex0lwbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zex0lwbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:filter-off-filled" /></template>
