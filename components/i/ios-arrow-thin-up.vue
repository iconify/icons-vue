<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z41zfsbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z41zfsbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-arrow-thin-up" /></template>
