<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7bbisuaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b7bbisuaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-circle-down-right" /></template>
