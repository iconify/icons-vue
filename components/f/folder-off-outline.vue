<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tacc1hwhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tacc1hwhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-off-outline" /></template>
