<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5zlcr8ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="j5zlcr8ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:gamepad-right-fill" /></template>
