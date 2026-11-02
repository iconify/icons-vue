<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh7e7ubci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh7e7ubci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-minus-line" /></template>
