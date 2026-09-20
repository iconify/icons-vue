<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wha5l4bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wha5l4bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-down-square-filled" /></template>
