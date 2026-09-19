<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scm3apdxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="scm3apdxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:lattice-pattern" /></template>
