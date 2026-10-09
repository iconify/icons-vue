<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8odd-vsc.css';
import '../../css/o/orpof4bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h8odd-vsc"/><path class="orpof4bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fast-forward-48-bold" /></template>
