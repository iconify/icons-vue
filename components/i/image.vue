<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1xpetzsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="l1xpetzsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:image" /></template>
