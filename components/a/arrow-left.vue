<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-2najbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i-2najbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:arrow-left" /></template>
