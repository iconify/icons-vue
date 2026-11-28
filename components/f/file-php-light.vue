<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w48vkb1yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="w48vkb1yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-php-light" /></template>
