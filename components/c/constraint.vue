<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r14ny_bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r14ny_bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:constraint" /></template>
