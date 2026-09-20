<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/redtqtbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="redtqtbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:baguette" /></template>
