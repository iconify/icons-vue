<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p61lf_73v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p61lf_73v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:component-48-bold" /></template>
