<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugtzrtb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugtzrtb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:camera-flip-filled" /></template>
