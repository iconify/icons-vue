<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzd046bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzd046bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:balloon-2-fill" /></template>
