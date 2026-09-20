<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su61edt6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="su61edt6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:expand-window-2-solid" /></template>
