<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq7gy1ill.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xq7gy1ill"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:folder-delete-solid" /></template>
