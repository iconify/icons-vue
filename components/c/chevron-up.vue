<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvrg0dbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tvrg0dbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:chevron-up" /></template>
