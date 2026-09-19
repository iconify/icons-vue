<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uii94qbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="uii94qbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:collection-pdf" /></template>
