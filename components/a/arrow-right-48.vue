<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9t00gb6u.css';
import '../../css/f/fqwpfx1sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x9t00gb6u"/><path class="fqwpfx1sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-right-48" /></template>
