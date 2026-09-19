<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqia3ccfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="lqia3ccfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:form" /></template>
