<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx2qjgbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="qx2qjgbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:csharp" /></template>
