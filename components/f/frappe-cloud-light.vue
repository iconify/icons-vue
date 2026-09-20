<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mehs67sax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mehs67sax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-cloud-light" /></template>
