<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7n0tensn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s7n0tensn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:blood-donate-drop-solid" /></template>
