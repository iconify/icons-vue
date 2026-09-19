<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whf6808kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whf6808kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:columns-four" /></template>
