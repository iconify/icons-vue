<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz-ju9arh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz-ju9arh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:drill" /></template>
