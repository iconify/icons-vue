<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbyd0vbew.css';
import '../../css/b/bhk7a-jqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tbyd0vbew"/><path class="bhk7a-jqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-up-left-48-bold" /></template>
