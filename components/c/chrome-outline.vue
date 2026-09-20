<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb0yl91bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jb0yl91bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:chrome-outline" /></template>
