<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdsia9gjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdsia9gjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:input-box" /></template>
