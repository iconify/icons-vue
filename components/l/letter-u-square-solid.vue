<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-4tdoufz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-4tdoufz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-u-square-solid" /></template>
