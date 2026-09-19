<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4miyyboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="c4miyyboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:glue" /></template>
