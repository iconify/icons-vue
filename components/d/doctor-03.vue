<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsj_mfb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsj_mfb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:doctor-03" /></template>
