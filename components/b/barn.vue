<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcmoj76zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fcmoj76zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:barn" /></template>
