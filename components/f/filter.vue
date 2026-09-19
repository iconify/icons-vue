<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imx_s_bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="imx_s_bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:filter" /></template>
