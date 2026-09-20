<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh8bykbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wh8bykbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bear-spray-can-with-spray" /></template>
