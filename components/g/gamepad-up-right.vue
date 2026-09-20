<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2511yb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="q2511yb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:gamepad-up-right" /></template>
