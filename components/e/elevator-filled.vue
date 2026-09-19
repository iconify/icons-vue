<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yefs43rzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yefs43rzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:elevator-filled" /></template>
