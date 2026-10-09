<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwrb__blp.css';
import '../../css/t/tp6desghj.css';
import '../../css/o/o7vde7bur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pwrb__blp"/><path class="tp6desghj"/><path class="o7vde7bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:analytics-48" /></template>
