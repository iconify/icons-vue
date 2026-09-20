<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aet0isvzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aet0isvzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-expand-solid" /></template>
