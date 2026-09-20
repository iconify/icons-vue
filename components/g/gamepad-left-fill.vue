<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5fdbb3rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="f5fdbb3rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:gamepad-left-fill" /></template>
