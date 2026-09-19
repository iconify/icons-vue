<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfe71db5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="tfe71db5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:italic" /></template>
