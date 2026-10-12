<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxvst7bbl.css';
import '../../css/s/syk3pwbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qxvst7bbl"/><path class="syk3pwbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cow-48" /></template>
