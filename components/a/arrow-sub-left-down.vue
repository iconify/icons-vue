<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqd4v7b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqd4v7b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-sub-left-down" /></template>
