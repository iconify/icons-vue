<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giv3sgb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giv3sgb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:camera-lens-3" /></template>
