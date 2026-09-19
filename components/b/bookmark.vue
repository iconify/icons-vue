<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adz4t67qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adz4t67qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:bookmark" /></template>
