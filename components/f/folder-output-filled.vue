<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-md9gy6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-md9gy6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-output-filled" /></template>
