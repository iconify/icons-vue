<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d07b03tyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="d07b03tyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:info" /></template>
