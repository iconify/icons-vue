<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkmm-1g0c.css';
import '../../css/h/h1ytemzns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="tkmm-1g0c"/><path class="h1ytemzns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:globe-options" /></template>
