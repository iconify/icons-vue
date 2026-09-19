<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h30_pj2ow.css';
import '../../css/t/tmh0ewb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h30_pj2ow"/><path class="tmh0ewb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-right-alt" /></template>
