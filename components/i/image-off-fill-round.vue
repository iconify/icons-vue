<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw66n2btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw66n2btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-off-fill-round" /></template>
