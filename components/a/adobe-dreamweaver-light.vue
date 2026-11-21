<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydxj9ob5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ydxj9ob5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-dreamweaver-light" /></template>
