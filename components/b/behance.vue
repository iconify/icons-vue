<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tav3z1unb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":830,"height":750};
const content = `<path class="tav3z1unb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:behance" /></template>
