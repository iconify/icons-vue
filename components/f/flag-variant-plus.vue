<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6zmu34di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6zmu34di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flag-variant-plus" /></template>
