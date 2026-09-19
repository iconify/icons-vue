<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsl2m0bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hsl2m0bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:globe-asia" /></template>
