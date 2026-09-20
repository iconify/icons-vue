<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb_6qrbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb_6qrbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:axis-bank" /></template>
