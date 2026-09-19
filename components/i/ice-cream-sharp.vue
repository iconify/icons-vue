<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm0h_i9fz.css';
import '../../css/g/gt-wt7bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bm0h_i9fz"/><path class="gt-wt7bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ice-cream-sharp" /></template>
