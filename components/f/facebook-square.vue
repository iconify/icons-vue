<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je9v0ja6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="je9v0ja6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:facebook-square" /></template>
