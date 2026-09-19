<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czzrfsbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czzrfsbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:horizontal-right" /></template>
