<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfplscndj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qfplscndj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:compass-small-filled" /></template>
