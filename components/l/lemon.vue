<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_t27sw-g.css';
import '../../css/x/x4c4cxb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_t27sw-g"/><path class="x4c4cxb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:lemon" /></template>
