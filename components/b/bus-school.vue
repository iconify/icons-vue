<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfth7oboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfth7oboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bus-school" /></template>
