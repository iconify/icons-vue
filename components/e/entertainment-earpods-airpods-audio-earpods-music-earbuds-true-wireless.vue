<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okwossb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="okwossb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:entertainment-earpods-airpods-audio-earpods-music-earbuds-true-wireless" /></template>
