<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gouxmnbpb.css';
import '../../css/k/kqpq3jb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gouxmnbpb"/><path class="kqpq3jb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-floppy-disk" /></template>
