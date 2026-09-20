<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4su09bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4su09bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:clock-eight" /></template>
