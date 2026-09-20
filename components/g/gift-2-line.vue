<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymyvlikmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymyvlikmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gift-2-line" /></template>
