<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_87cvbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l_87cvbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coffin-with-angel-moroni" /></template>
