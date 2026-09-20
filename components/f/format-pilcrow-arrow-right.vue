<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlvk1-bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlvk1-bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-pilcrow-arrow-right" /></template>
