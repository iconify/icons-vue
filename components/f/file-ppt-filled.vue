<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwnt7jijk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jwnt7jijk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-ppt-filled" /></template>
