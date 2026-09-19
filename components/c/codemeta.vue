<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-neh6-iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":436,"height":512};
const content = `<path class="s-neh6-iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:codemeta" /></template>
