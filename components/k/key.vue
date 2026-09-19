<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw5x8425k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw5x8425k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:key" /></template>
