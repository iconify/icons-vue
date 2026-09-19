<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmw-2dj0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mmw-2dj0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-u-turn" /></template>
