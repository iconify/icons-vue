<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxefnowdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxefnowdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:globe-x" /></template>
