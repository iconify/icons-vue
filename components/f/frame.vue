<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxown8zph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nxown8zph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:frame" /></template>
