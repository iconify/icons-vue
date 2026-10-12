<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uku-79btt.css';
import '../../css/f/fbdvput5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uku-79btt"/><path class="fbdvput5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chalkboard-48" /></template>
