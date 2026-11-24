<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqpt0ub4e.css';
import '../../css/h/hpyrhjbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqpt0ub4e"/><path class="hpyrhjbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layer-arrow-down-filled" /></template>
