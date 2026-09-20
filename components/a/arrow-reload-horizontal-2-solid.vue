<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqvo3ybzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jqvo3ybzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-reload-horizontal-2-solid" /></template>
