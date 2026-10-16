<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oegrs6bql.css';
import '../../css/e/e5hbpvfpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oegrs6bql"/><path class="e5hbpvfpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-tax-48" /></template>
