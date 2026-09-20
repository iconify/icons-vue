<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q09t21ylq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q09t21ylq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:display-outline" /></template>
