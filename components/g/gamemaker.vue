<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ril_axbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ril_axbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gamemaker" /></template>
