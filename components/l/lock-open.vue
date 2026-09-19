<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulycovzbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulycovzbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:lock-open" /></template>
