<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovlsupbow.css';
import '../../css/e/ep-e4lbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ovlsupbow"/><path class="ep-e4lbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-lock-48" /></template>
