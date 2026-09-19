<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2183srfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2183srfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-left-04" /></template>
