<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azbzlppnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azbzlppnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:laptop-remove" /></template>
