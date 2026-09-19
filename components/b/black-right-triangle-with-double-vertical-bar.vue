<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7p52cbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="t7p52cbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-right-triangle-with-double-vertical-bar" /></template>
