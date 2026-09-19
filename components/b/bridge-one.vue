<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m874v74cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m874v74cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bridge-one" /></template>
