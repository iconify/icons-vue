<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgzirsm5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgzirsm5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:libra-line" /></template>
