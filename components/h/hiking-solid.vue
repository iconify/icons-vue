<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uabfv_bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uabfv_bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hiking-solid" /></template>
