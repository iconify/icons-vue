<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3eiqojot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c3eiqojot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:common-workflow-language" /></template>
