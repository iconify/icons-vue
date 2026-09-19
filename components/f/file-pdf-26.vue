<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hay_dtbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":26};
const content = `<path class="hay_dtbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-pdf-26" /></template>
