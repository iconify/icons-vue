<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rznww9boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rznww9boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:asymptote" /></template>
