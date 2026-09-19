<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chcka6bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="chcka6bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-vector-filled" /></template>
