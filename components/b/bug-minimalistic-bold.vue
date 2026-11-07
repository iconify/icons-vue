<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkonzhevj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dkonzhevj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bug-minimalistic-bold" /></template>
