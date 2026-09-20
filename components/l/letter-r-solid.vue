<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysgew1w2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysgew1w2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-r-solid" /></template>
