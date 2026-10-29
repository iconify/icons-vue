<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbioanofn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbioanofn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-t" /></template>
