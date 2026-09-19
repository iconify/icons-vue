<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guhg6-y-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="guhg6-y-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:border-top" /></template>
