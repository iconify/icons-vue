<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8b-mib4c.css';
import '../../css/v/vs9a-qkba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="h8b-mib4c"/><path class="vs9a-qkba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-left-fill-12" /></template>
