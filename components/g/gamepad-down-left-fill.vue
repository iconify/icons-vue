<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxztuo_we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="kxztuo_we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:gamepad-down-left-fill" /></template>
