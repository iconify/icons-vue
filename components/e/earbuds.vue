<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek3flgivq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek3flgivq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:earbuds" /></template>
