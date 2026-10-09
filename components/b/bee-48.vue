<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppl_-uorl.css';
import '../../css/u/uso6srbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ppl_-uorl"/><path class="uso6srbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bee-48" /></template>
