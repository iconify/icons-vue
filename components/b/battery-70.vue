<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq8je227t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq8je227t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-70" /></template>
