<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjptt3u3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xjptt3u3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:cafe" /></template>
