<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfv8xnp-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfv8xnp-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:figma-fill-round" /></template>
