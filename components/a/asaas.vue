<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndm8ctsqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":17};
const content = `<path class="ndm8ctsqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:asaas" /></template>
