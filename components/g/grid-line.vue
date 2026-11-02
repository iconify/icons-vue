<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqau3ebwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqau3ebwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grid-line" /></template>
