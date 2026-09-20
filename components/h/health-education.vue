<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6mhhybdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":65,"height":64};
const content = `<path class="p6mhhybdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:health-education" /></template>
