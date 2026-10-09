<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4zhywu2u.css';
import '../../css/s/sbj00_4pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p4zhywu2u"/><path class="sbj00_4pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-right-down-48" /></template>
