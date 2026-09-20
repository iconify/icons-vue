<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yljak-bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="yljak-bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:line-y" /></template>
