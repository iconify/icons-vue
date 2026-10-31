<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdz1nabay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdz1nabay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:container-gloss" /></template>
