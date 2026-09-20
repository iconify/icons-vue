<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dspnf0f_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dspnf0f_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-dash-fill" /></template>
