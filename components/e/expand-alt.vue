<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia_q_wbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ia_q_wbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:expand-alt" /></template>
