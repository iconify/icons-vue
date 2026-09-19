<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmvk8nhzs.css';
import '../../css/t/tza-ysb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmvk8nhzs"/><path class="tza-ysb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:handheld" /></template>
