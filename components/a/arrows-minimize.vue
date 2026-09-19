<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arpl6mdzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="arpl6mdzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:arrows-minimize" /></template>
