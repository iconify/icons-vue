<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lub4f059b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lub4f059b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:code-pull-request-xmark" /></template>
