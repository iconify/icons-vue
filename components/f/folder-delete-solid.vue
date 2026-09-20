<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggu7abcoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ggu7abcoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:folder-delete-solid" /></template>
