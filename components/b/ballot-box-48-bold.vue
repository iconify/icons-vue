<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4geewbmp.css';
import '../../css/e/e57f5cgnd.css';
import '../../css/l/lo0zzvbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j4geewbmp"/><path class="e57f5cgnd"/><path class="lo0zzvbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ballot-box-48-bold" /></template>
