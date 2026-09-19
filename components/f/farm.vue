<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn_1_85bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn_1_85bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:farm" /></template>
