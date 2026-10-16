<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-w1mof7v.css';
import '../../css/l/lzskzeb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b-w1mof7v"/><path class="lzskzeb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:aspect-ratio-20-bold" /></template>
