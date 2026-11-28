<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exkh_2n1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exkh_2n1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:fire-truck-solid" /></template>
