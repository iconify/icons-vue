<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir025xb6j.css';
import '../../css/k/kgirabbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ir025xb6j"/><path class="kgirabbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dispatch-48" /></template>
