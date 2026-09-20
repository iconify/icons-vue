<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wablsl4pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wablsl4pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:h-2" /></template>
