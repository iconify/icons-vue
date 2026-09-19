<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9j79ebqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":440};
const content = `<path class="v9j79ebqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:bike" /></template>
