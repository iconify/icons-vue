<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9p9e2bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9p9e2bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:brush" /></template>
