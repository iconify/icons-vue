<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycs9h4bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ycs9h4bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:dizzy" /></template>
