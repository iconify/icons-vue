<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga1wr6bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ga1wr6bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:avro" /></template>
