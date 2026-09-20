<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_jt8jbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_jt8jbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calculator-bold" /></template>
