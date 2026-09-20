<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8smtgk6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="i8smtgk6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:interpreter-services" /></template>
