<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-r24r9hl.css';
import '../../css/w/w7jijrg7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f-r24r9hl"/><path class="w7jijrg7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-secure" /></template>
