<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2buqlbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2buqlbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-horizontal-distribute-start-fill" /></template>
