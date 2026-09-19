<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbj_rt5nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbj_rt5nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:copy" /></template>
