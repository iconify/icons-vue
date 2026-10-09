<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otpi8ybma.css';
import '../../css/r/rhawa5b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="otpi8ybma"/><path class="rhawa5b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:alert-octagon-48-bold" /></template>
