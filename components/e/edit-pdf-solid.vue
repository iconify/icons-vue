<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edz5fexnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="edz5fexnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:edit-pdf-solid" /></template>
