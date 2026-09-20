<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqtfli2lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqtfli2lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-left" /></template>
