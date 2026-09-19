<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3ykk1bme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3ykk1bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:funnel" /></template>
