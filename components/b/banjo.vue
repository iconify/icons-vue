<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2wf-5mat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="e2wf-5mat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:banjo" /></template>
