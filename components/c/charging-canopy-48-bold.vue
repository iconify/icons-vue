<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alk5rr8yk.css';
import '../../css/b/bclccdbvo.css';
import '../../css/e/eveyughjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="alk5rr8yk"/><path class="bclccdbvo"/><path class="eveyughjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charging-canopy-48-bold" /></template>
