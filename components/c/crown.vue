<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj42u0b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zj42u0b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:crown" /></template>
