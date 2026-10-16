<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbi-s8b7c.css';
import '../../css/z/z4sj3ixdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lbi-s8b7c"/><path class="z4sj3ixdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:air-quality-48" /></template>
