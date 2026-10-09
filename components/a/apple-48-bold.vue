<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq9rmtbnw.css';
import '../../css/g/g77nglpfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gq9rmtbnw"/><path class="g77nglpfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:apple-48-bold" /></template>
