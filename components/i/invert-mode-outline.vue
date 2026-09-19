<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w84vznkgo.css';
import '../../css/e/eg1ps4yde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="w84vznkgo"/><path class="eg1ps4yde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:invert-mode-outline" /></template>
