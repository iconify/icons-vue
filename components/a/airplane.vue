<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofbq-ccag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ofbq-ccag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:airplane" /></template>
