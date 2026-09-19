<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt4pc4b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yt4pc4b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:deezer" /></template>
