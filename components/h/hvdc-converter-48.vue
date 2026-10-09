<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f76ef2b7k.css';
import '../../css/s/s0byieb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f76ef2b7k"/><path class="s0byieb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hvdc-converter-48" /></template>
