<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3i123b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3i123b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:glass-full-filled" /></template>
