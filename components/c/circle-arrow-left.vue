<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrk2c_o7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="mrk2c_o7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:circle-arrow-left" /></template>
