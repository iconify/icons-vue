<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skiszgg3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="skiszgg3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:magnify-minus" /></template>
