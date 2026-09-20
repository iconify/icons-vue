<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9-xbkb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p9-xbkb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:horse-running" /></template>
