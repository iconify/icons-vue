<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl2t54zdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl2t54zdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bookmark" /></template>
