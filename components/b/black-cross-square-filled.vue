<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5tnxjw_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="q5tnxjw_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-cross-square-filled" /></template>
