<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h911x3vnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="h911x3vnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:diagonal-cross" /></template>
