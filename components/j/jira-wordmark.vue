<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwvdk2bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mwvdk2bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:jira-wordmark" /></template>
