<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-zvam3xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="f-zvam3xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-symlink-file" /></template>
