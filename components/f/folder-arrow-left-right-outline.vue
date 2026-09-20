<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x626upbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x626upbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-arrow-left-right-outline" /></template>
