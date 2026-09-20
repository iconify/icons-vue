<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz2c4cb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz2c4cb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-riyal" /></template>
