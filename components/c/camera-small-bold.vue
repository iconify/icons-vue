<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph8967bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph8967bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:camera-small-bold" /></template>
