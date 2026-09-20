<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um4ht9bsf.css';
import '../../css/k/kvdfrrbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="um4ht9bsf"/><path class="kvdfrrbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:cello-16" /></template>
