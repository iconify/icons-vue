<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zanasbbem.css';
import '../../css/i/iqca1hbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zanasbbem"/><path class="iqca1hbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:boiler-48-bold" /></template>
