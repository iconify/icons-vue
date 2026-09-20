<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm5xiid0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="bm5xiid0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:code-s" /></template>
