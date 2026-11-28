<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_1fmbd2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_1fmbd2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bone-alert" /></template>
