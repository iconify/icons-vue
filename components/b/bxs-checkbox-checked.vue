<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svo32d08a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svo32d08a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-checkbox-checked" /></template>
