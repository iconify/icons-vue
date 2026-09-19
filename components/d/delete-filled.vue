<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwum6gbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nwum6gbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:delete-filled" /></template>
