<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhfbtcy6k.css';
import '../../css/c/cf6_evf1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bhfbtcy6k"/><path class="cf6_evf1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:deforestation-48-bold" /></template>
