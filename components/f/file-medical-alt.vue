<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0d6phkfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t0d6phkfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:file-medical-alt" /></template>
