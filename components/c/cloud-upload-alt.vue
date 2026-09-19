<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6soyqb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="x6soyqb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:cloud-upload-alt" /></template>
