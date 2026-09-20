<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm-0kub9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm-0kub9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:functions" /></template>
