<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j99vy2bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":401,"height":512};
const content = `<path class="j99vy2bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:binder" /></template>
