<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k800nzeoy.css';
import '../../css/e/eawggbbqu.css';
import '../../css/z/z7c6bib6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k800nzeoy"/><path class="eawggbbqu"/><path class="z7c6bib6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crib-48" /></template>
