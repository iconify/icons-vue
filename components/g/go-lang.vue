<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfumpbcnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfumpbcnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:go-lang" /></template>
