<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhzuk02qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yhzuk02qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:link-chain" /></template>
