<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmwimnb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmwimnb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:biscuit-plus-outline" /></template>
