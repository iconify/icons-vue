<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbwrax-_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xbwrax-_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:database-stroke-20" /></template>
