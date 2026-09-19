<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arezy-bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="arezy-bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:archive" /></template>
