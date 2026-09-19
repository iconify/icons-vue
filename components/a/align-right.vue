<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hek2idb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hek2idb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:align-right" /></template>
