<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw1zb91cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw1zb91cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:forward-slash-square-filled" /></template>
