<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw2nm3b1a.css';
import '../../css/b/bib7mgb4o.css';
import '../../css/n/nidx4if6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cw2nm3b1a"/><path class="bib7mgb4o"/><path class="nidx4if6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:guitar-20" /></template>
