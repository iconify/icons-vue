<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8ytktbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":488};
const content = `<path class="h8ytktbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:linkedin-alt" /></template>
