<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_e70abvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_e70abvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:certificate-2-fill" /></template>
