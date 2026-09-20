<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbpddjans.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbpddjans"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:badge-minus" /></template>
