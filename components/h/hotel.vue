<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tih_i84ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tih_i84ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hotel" /></template>
