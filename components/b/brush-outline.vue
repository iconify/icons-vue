<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6vrhzb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a6vrhzb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:brush-outline" /></template>
