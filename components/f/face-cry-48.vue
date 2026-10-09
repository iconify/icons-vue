<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hac57wbhi.css';
import '../../css/f/fhq5d2cfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hac57wbhi"/><path class="fhq5d2cfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:face-cry-48" /></template>
