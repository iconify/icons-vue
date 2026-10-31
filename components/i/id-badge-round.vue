<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt5ioiiqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt5ioiiqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:id-badge-round" /></template>
