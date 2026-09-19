<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km2skgx_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="km2skgx_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bluetooth-tag-solid" /></template>
