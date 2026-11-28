<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb1bm54nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bb1bm54nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:award-solid" /></template>
