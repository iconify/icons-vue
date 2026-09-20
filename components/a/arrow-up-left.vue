<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt78ukgqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="xt78ukgqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:arrow-up-left" /></template>
