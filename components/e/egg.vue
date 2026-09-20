<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saj0lv78a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="saj0lv78a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:egg" /></template>
