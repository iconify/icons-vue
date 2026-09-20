<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwr2zcchh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vwr2zcchh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:columns" /></template>
