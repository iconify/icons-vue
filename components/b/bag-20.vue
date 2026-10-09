<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oora6eb1h.css';
import '../../css/l/l0_kzwbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oora6eb1h"/><path class="l0_kzwbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bag-20" /></template>
