<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb6w09bir.css';
import '../../css/o/o8fo-jx8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wb6w09bir"/><path class="o8fo-jx8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:eject" /></template>
