<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trcsivmik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trcsivmik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:caret-right-square-filled" /></template>
