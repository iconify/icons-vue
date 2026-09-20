<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qni8_cbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qni8_cbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:dot-fill-24" /></template>
