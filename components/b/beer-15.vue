<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu9s651lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bu9s651lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:beer-15" /></template>
