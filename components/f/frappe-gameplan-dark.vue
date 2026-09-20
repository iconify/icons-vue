<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izucyb58q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="izucyb58q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-gameplan-dark" /></template>
