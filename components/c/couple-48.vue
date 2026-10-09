<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnge4obvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cnge4obvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:couple-48" /></template>
