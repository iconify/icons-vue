<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1ck9ujgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="v1ck9ujgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:crane-4" /></template>
