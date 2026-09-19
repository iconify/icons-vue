<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e77eg_m-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e77eg_m-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:landmark-filled" /></template>
