<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jed2ko24i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1280};
const content = `<path class="jed2ko24i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:lastfm" /></template>
