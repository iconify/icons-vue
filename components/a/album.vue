<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frkxnd0nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":596,"height":717};
const content = `<path class="frkxnd0nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:album" /></template>
