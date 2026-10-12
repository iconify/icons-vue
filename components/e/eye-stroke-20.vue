<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob_63mboo.css';
import '../../css/w/w55hdcgdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ob_63mboo"/><path class="w55hdcgdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:eye-stroke-20" /></template>
