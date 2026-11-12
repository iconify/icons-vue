<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hukoubbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hukoubbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:backrest-light" /></template>
