<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l56gk9tyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="l56gk9tyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:box-multiply-solid" /></template>
