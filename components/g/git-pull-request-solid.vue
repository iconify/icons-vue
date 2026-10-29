<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjpp62bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjpp62bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-pull-request-solid" /></template>
