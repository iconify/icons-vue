<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdc73lbzg.css';
import '../../css/u/uqg7dcvvc.css';
import '../../css/k/kareh6bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bdc73lbzg"/><path class="uqg7dcvvc"/><path class="kareh6bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:guitar-48" /></template>
