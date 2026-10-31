<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byq9j8u9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byq9j8u9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-left-to-line-fill-round" /></template>
