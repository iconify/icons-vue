<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkljhobag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkljhobag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:code-solid" /></template>
