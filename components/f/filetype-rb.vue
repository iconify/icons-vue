<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mujp0acni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mujp0acni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-rb" /></template>
