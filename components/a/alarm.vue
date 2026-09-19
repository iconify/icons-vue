<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh27cfbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="lh27cfbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:alarm" /></template>
