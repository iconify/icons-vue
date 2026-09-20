<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx2dvxl_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx2dvxl_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:expand-diagonal-duotone" /></template>
