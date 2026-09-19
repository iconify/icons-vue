<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrtsf18ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrtsf18ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bookmark-heart" /></template>
