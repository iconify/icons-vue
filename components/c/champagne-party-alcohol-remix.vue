<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0r-2hb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j0r-2hb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:champagne-party-alcohol-remix" /></template>
