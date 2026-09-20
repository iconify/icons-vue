<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssr-jbkxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssr-jbkxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:element3-filled" /></template>
