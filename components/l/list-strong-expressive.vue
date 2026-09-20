<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-59_6bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-59_6bqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:list-strong-expressive" /></template>
