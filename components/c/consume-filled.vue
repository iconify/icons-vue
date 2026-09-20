<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8dmtfb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w8dmtfb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:consume-filled" /></template>
