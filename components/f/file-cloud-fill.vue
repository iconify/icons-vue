<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it_k10b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it_k10b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-cloud-fill" /></template>
