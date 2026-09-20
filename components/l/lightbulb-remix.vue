<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctfr756up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ctfr756up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:lightbulb-remix" /></template>
