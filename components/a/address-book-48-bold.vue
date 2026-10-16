<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djvqpt-nt.css';
import '../../css/i/i3kvsjzmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="djvqpt-nt"/><path class="i3kvsjzmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:address-book-48-bold" /></template>
