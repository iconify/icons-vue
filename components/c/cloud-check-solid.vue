<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvb3ftkaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yvb3ftkaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cloud-check-solid" /></template>
