<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw36nxb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw36nxb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:link-outline" /></template>
