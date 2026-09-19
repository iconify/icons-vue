<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p89tr8rsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p89tr8rsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:arrow-circle-left" /></template>
