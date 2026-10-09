<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3wq640fi.css';
import '../../css/x/x59ggbc2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m3wq640fi"/><path class="x59ggbc2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hanger-48" /></template>
