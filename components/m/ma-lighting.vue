<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmy68d9hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmy68d9hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ma-lighting" /></template>
