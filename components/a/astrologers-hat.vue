<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upnhazbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="upnhazbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:astrologers-hat" /></template>
