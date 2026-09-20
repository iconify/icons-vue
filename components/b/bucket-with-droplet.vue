<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvjhkcbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nvjhkcbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bucket-with-droplet" /></template>
