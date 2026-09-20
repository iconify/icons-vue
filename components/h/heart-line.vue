<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nklcr7bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nklcr7bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heart-line" /></template>
