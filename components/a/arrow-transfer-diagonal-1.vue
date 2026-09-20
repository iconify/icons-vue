<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-7-34bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="b-7-34bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-transfer-diagonal-1" /></template>
