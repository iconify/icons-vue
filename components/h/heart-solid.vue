<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsdz_cbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsdz_cbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-solid" /></template>
