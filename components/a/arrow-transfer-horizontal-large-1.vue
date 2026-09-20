<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgn2xtoqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgn2xtoqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:arrow-transfer-horizontal-large-1" /></template>
