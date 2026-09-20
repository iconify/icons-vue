<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjdfyacqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gjdfyacqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-erpnext-light" /></template>
