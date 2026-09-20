<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1qgs8v4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1qgs8v4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-bar-to-up" /></template>
