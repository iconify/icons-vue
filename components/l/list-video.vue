<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nonm9dbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nonm9dbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:list-video" /></template>
