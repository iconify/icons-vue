<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac1bsobcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":150,"height":512};
const content = `<path class="ac1bsobcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:cwl" /></template>
