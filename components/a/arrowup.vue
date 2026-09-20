<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-kfe4brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v-kfe4brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:arrowup" /></template>
