<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn_mmh6jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn_mmh6jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-pound-outline" /></template>
