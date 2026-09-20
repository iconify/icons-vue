<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu_d6gbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tu_d6gbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:female-solid" /></template>
