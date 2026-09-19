<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2h3c5b8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2h3c5b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-rain" /></template>
