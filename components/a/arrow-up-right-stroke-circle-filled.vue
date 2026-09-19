<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtshnyb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtshnyb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-right-stroke-circle-filled" /></template>
