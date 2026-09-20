<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlfn-lb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlfn-lb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:brightness-filled" /></template>
