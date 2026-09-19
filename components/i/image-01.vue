<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkc0vy_ze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkc0vy_ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:image-01" /></template>
