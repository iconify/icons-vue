<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkescdcic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkescdcic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:http-get" /></template>
