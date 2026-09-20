<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw_vlx9eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw_vlx9eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:code-circle3-filled" /></template>
