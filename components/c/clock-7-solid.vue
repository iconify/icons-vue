<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_tsxub1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_tsxub1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clock-7-solid" /></template>
