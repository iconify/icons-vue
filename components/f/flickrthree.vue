<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tze1n8bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":614};
const content = `<path class="tze1n8bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:flickrthree" /></template>
