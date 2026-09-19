<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvbel5oat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="dvbel5oat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:flickr" /></template>
