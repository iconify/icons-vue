<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtl8plxof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtl8plxof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:butterfly-filled" /></template>
