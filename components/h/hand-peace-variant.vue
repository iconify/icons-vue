<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm0nid0uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm0nid0uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-peace-variant" /></template>
