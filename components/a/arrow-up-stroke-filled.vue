<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcij9pukf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcij9pukf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-stroke-filled" /></template>
