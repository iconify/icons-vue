<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olpxcdbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="olpxcdbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:fortran" /></template>
