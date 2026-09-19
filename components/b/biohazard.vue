<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9yob9b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="r9yob9b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:biohazard" /></template>
