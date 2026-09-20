<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpqxt4psy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="xpqxt4psy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:gamepad-down-right" /></template>
