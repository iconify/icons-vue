<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2o8lkbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s2o8lkbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cloud-refresh-solid" /></template>
