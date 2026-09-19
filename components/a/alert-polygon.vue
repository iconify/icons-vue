<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt3_vab_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":448};
const content = `<path class="kt3_vab_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:alert-polygon" /></template>
