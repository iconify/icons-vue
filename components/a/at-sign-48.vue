<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3eacdoxs.css';
import '../../css/m/m9i0cybsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j3eacdoxs"/><path class="m9i0cybsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:at-sign-48" /></template>
