<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-xqgtvwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-xqgtvwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-edit-corner-fill-round" /></template>
