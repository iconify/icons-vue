<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm4f9d33i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="sm4f9d33i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:gamepad-up" /></template>
