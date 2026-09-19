<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyu939b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vyu939b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:jira" /></template>
