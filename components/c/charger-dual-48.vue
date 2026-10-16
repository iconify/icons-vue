<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8o5yujab.css';
import '../../css/q/qdez92c3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r8o5yujab"/><path class="qdez92c3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-dual-48" /></template>
