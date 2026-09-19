<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxv6y6bpx.css';
import '../../css/k/kdqyt0wqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxv6y6bpx"/><path class="kdqyt0wqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:headphone-alt-2-filled" /></template>
