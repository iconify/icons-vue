<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj7h6gphw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1280};
const content = `<path class="lj7h6gphw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:digg" /></template>
