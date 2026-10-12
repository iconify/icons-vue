<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wng9gxbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wng9gxbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:dot" /></template>
