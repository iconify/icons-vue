<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qse_z8bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qse_z8bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bean-fill" /></template>
