<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtmw03j5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtmw03j5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:clipboard-minus-line" /></template>
