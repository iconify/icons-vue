<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dctxs9-rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dctxs9-rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:binoculars" /></template>
