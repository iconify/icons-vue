<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up844cc5r.css';
import '../../css/p/p6cb9-b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up844cc5r"/><path class="p6cb9-b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:book-heart" /></template>
