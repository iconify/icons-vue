<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1cxg7g9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1cxg7g9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:corner-up-right-alt" /></template>
