<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x37y8kyft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x37y8kyft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:file-image-fill" /></template>
