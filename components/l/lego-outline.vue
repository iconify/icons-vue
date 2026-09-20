<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft9ancbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ft9ancbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:lego-outline" /></template>
