<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd9q9w1ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd9q9w1ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-terminator" /></template>
