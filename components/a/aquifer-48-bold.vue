<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alk5rr8yk.css';
import '../../css/n/nhgdse76r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="alk5rr8yk"/><path class="nhgdse76r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:aquifer-48-bold" /></template>
