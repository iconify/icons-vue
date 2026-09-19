<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugua35byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="ugua35byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:local-hospital" /></template>
