<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opuvz3osb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="opuvz3osb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:globe-outline-24px" /></template>
