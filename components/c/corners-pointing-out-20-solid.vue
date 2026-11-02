<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_76ry0sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="i_76ry0sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:corners-pointing-out-20-solid" /></template>
