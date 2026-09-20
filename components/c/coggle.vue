<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udbs4h_qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udbs4h_qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:coggle" /></template>
