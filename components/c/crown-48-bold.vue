<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4vc4jmhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z4vc4jmhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crown-48-bold" /></template>
