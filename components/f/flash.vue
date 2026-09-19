<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt2kzbb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":216,"height":432};
const content = `<path class="gt2kzbb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:flash" /></template>
