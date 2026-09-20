<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i15wu7f2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="i15wu7f2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-up-right" /></template>
