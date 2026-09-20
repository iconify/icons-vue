<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds08pm90k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds08pm90k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:baseten" /></template>
