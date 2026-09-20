<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3f8h8t0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x3f8h8t0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:hierarchy-line-1-flat" /></template>
