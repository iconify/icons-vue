<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s99qsccqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s99qsccqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:loop-24" /></template>
