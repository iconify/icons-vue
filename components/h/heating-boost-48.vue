<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-obboe6z.css';
import '../../css/u/u2ghli_7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k-obboe6z"/><path class="u2ghli_7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heating-boost-48" /></template>
