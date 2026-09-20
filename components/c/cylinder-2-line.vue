<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyx9a9liv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyx9a9liv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cylinder-2-line" /></template>
