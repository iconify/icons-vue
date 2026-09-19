<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgsbk7zch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":512};
const content = `<path class="kgsbk7zch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:codiepie" /></template>
