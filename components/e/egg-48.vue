<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa0o18b5j.css';
import '../../css/a/argg3sbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fa0o18b5j"/><path class="argg3sbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:egg-48" /></template>
