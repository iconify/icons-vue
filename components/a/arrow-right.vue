<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti9vqc5io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti9vqc5io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:arrow-right" /></template>
