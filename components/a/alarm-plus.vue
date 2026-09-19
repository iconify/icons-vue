<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1q-f9vcx.css';
import '../../css/u/uyp_7-bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1q-f9vcx"/><path class="uyp_7-bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alarm-plus" /></template>
