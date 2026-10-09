<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w18tredqi.css';
import '../../css/a/autp9p4ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w18tredqi"/><path class="autp9p4ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:files-48" /></template>
