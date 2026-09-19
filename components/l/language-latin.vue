<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecsl_f_4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ecsl_f_4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-latin" /></template>
