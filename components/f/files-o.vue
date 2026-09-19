<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5t320bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="x5t320bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:files-o" /></template>
