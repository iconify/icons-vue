<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_4sz5s7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_4sz5s7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-table" /></template>
