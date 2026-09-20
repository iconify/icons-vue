<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_z4_2wnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y_z4_2wnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:fragile-solid" /></template>
