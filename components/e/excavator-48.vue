<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbhfztbdk.css';
import '../../css/s/s3cdewurv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rbhfztbdk"/><path class="s3cdewurv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:excavator-48" /></template>
