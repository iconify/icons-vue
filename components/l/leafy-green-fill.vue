<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_508vd_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_508vd_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:leafy-green-fill" /></template>
