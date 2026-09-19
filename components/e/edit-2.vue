<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx9y0p8vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx9y0p8vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:edit-2" /></template>
