<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxb2f-u5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qxb2f-u5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:copy-arrow-right" /></template>
