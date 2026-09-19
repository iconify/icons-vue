<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si0jw2byf.css';
import '../../css/r/r7dafkb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="si0jw2byf"/><path class="r7dafkb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bookmarks-sharp" /></template>
