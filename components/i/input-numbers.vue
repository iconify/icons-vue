<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyzek-p_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fyzek-p_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:input-numbers" /></template>
