<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znpeg-p4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="znpeg-p4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:grip-horizontal" /></template>
