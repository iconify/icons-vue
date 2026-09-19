<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twtwy1b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="twtwy1b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:link-slash" /></template>
