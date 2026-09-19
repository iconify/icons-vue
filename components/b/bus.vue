<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmxbg2yju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="gmxbg2yju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bus" /></template>
