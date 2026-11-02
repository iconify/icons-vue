<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgimc7f1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgimc7f1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:car-2-line" /></template>
