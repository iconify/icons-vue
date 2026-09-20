<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7cqk3gaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7cqk3gaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-down-circle" /></template>
