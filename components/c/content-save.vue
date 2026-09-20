<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1m8t89qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o1m8t89qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-save" /></template>
