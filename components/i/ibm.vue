<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk9d-zsqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mk9d-zsqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:ibm" /></template>
