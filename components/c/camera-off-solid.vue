<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt1trnmll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt1trnmll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:camera-off-solid" /></template>
