<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilma5fblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilma5fblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-left-from-line" /></template>
