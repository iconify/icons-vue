<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdh5ety7c.css';
import '../../css/k/ktbpolgkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hdh5ety7c"/><path class="ktbpolgkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:copilot-48" /></template>
