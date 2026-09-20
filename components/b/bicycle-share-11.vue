<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-9b1fark.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="i-9b1fark"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bicycle-share-11" /></template>
