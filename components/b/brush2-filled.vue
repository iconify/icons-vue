<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmv-ybh1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmv-ybh1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:brush2-filled" /></template>
