<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l92m32boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="l92m32boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:imdb" /></template>
