<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9v47kbel.css';
import '../../css/e/e8kp6ybjw.css';
import '../../css/o/o9b-4cbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q9v47kbel"/><path class="e8kp6ybjw"/><path class="o9b-4cbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:directions-48" /></template>
