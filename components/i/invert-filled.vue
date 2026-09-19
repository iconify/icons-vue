<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpxmm_7co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpxmm_7co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:invert-filled" /></template>
