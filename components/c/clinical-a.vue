<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skhz5ybrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="skhz5ybrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:clinical-a" /></template>
