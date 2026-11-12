<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui9_-gb1z.css';
import '../../css/h/hngcoxbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ui9_-gb1z"/><path class="hngcoxbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:baikal-light" /></template>
