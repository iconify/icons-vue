<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uer6x4btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uer6x4btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:extension-puzzle" /></template>
