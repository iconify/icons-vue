<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0a113bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="p0a113bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:folder" /></template>
