<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tubl6gxzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tubl6gxzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:code-commit-horizontal" /></template>
