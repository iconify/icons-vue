<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymglykxtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ymglykxtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-2-outline" /></template>
