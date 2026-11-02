<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrcd60buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrcd60buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-indent-decrease-line" /></template>
