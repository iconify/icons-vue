<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_7pe4bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_7pe4bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:label-folder-tag-solid" /></template>
