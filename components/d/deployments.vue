<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxyw-3zpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cxyw-3zpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:deployments" /></template>
