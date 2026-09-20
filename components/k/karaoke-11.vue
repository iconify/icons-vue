<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur95pabmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ur95pabmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:karaoke-11" /></template>
