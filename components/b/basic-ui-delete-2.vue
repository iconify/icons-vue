<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k42f7rbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k42f7rbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-delete-2" /></template>
