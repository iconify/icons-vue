<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nplvzg3tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nplvzg3tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:code-xml" /></template>
