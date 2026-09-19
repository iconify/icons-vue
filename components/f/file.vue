<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ochfh37om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ochfh37om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:file" /></template>
