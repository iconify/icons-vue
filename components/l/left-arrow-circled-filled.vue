<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve2fb11kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ve2fb11kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:left-arrow-circled-filled" /></template>
