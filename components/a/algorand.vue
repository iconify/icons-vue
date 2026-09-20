<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucv0ic1km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucv0ic1km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:algorand" /></template>
