<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp5b8z1rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp5b8z1rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:giggle-filled" /></template>
