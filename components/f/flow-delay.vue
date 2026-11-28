<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs1_ig4jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs1_ig4jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-delay" /></template>
