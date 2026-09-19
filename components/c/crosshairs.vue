<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxxbk6bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="jxxbk6bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:crosshairs" /></template>
