<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npkghyb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="npkghyb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:check-flat" /></template>
