<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlgozrxrt.css';
import '../../css/h/hztm1ryfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlgozrxrt"/><path class="hztm1ryfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:heart-square" /></template>
