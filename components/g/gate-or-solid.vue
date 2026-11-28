<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqv-_cn3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqv-_cn3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gate-or-solid" /></template>
