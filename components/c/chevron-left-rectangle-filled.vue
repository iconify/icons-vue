<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zez2vnb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zez2vnb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-left-rectangle-filled" /></template>
