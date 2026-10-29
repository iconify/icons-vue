<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwamgkbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwamgkbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-dollar-sign-solid" /></template>
