<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjrt-gnxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjrt-gnxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ai21labs-jamba" /></template>
