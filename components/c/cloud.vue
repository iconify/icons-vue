<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk2_vebjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk2_vebjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud" /></template>
