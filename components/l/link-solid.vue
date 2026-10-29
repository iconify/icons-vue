<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf17-sblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf17-sblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:link-solid" /></template>
