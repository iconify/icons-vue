<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzc_knbku.css';
import '../../css/g/g-6zg3hle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tzc_knbku"/><path class="g-6zg3hle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:inbox-48-bold" /></template>
