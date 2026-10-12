<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl0-fwb4k.css';
import '../../css/o/oxs1yxfms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gl0-fwb4k"/><path class="oxs1yxfms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:brain-48" /></template>
