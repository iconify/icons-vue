<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksu31ioyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b ksu31ioyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circle-dashed-half-filled" /></template>
