<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1p8q7b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1p8q7b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:download-2-fill" /></template>
