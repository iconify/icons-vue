<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5ew9t0my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5ew9t0my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:id-card" /></template>
