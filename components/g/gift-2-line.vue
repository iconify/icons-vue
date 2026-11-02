<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7kigmb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7kigmb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gift-2-line" /></template>
