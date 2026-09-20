<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xadmng6km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xadmng6km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:git" /></template>
