<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7dywj58f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7dywj58f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-down-bold" /></template>
