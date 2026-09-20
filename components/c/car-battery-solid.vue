<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmqav161f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jmqav161f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:car-battery-solid" /></template>
