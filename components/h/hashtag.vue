<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek0dmobsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1728,"height":1536};
const content = `<path class="ek0dmobsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hashtag" /></template>
