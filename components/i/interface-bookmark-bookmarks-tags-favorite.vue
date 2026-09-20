<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmlcmxzsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tmlcmxzsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-bookmark-bookmarks-tags-favorite" /></template>
