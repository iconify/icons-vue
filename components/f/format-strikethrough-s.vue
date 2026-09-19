<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr_1osbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":432};
const content = `<path class="hr_1osbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-strikethrough-s" /></template>
