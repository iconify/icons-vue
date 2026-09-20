<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7zmlz6iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j7zmlz6iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dragon" /></template>
