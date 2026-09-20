<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kur-1kb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kur-1kb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:angle-left" /></template>
