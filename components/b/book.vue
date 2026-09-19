<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd1jb_bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd1jb_bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:book" /></template>
