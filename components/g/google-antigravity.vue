<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grgsbgnai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grgsbgnai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:google-antigravity" /></template>
