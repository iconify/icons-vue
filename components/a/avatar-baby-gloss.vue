<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx5164bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx5164bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-baby-gloss" /></template>
