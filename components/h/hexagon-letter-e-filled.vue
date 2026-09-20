<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muno4tb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muno4tb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-e-filled" /></template>
