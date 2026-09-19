<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzn7p-lkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mzn7p-lkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:emojisleep" /></template>
