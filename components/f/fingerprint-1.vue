<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljagxxz5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljagxxz5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:fingerprint-1" /></template>
