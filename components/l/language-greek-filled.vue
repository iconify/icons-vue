<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h876prbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="h876prbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-greek-filled" /></template>
