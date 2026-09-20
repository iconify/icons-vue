<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2l4x0b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l2l4x0b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:local-storage-folder-solid" /></template>
