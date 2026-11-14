<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd8e70owp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd8e70owp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:add-circle-half-dot" /></template>
