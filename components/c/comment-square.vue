<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr0lfd5rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sr0lfd5rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:comment-square" /></template>
