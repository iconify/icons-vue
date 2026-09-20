<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn3zg7bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn3zg7bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-ski" /></template>
