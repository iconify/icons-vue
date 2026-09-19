<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgm3asb6j.css';
import '../../css/p/pvkl0-bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lgm3asb6j"/><path class="pvkl0-bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-folder" /></template>
