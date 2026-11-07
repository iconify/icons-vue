<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g84mo7lfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g84mo7lfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bones-bold" /></template>
