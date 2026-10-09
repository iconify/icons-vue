<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnahg-_fl.css';
import '../../css/s/s9uxlpl9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cnahg-_fl"/><path class="s9uxlpl9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:jar-48-bold" /></template>
