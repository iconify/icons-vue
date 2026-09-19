<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsd1-gkmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1022};
const content = `<path class="dsd1-gkmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:campfire" /></template>
