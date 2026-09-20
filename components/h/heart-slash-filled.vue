<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iva73mbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iva73mbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:heart-slash-filled" /></template>
