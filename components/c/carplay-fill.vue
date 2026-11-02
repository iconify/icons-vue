<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m52gmm5_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m52gmm5_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:carplay-fill" /></template>
