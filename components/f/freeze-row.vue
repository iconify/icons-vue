<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u96y3zbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u96y3zbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:freeze-row" /></template>
