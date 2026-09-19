<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe_lsrbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xe_lsrbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:gnu-social" /></template>
