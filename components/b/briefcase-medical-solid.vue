<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2sknf2ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a2sknf2ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:briefcase-medical-solid" /></template>
