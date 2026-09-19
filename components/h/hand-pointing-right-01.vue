<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh9m-lbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh9m-lbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hand-pointing-right-01" /></template>
