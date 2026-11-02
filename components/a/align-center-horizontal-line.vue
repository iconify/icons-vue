<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmtwrx6vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmtwrx6vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-center-horizontal-line" /></template>
