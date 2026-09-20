<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j29yx1bwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j29yx1bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:long-arrow-alt-up-solid" /></template>
