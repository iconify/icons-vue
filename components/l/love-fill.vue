<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkr7ukbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkr7ukbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:love-fill" /></template>
