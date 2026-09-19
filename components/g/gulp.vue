<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmoujxouz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":225,"height":512};
const content = `<path class="vmoujxouz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:gulp" /></template>
