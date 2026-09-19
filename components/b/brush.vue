<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz57-0xqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gz57-0xqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:brush" /></template>
