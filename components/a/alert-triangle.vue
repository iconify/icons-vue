<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke7omlttr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ke7omlttr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:alert-triangle" /></template>
