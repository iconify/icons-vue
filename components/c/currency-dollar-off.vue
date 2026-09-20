<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_4bltbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_4bltbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-dollar-off" /></template>
