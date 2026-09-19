<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kraedhl7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kraedhl7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:git-pull-request-error" /></template>
