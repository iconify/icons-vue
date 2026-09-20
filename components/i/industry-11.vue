<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh_0adbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="wh_0adbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:industry-11" /></template>
