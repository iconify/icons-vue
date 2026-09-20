<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn48uir4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn48uir4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-monday" /></template>
