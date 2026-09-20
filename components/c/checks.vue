<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co5p8xbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co5p8xbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:checks" /></template>
