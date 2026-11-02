<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l33upq_ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l33upq_ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:knife-line" /></template>
