<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkelfkb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkelfkb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:kidneys-24px" /></template>
