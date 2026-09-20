<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_xk8wbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l_xk8wbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:desktop-code-solid" /></template>
