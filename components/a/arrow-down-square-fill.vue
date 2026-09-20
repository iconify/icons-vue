<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq95qdbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq95qdbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrow-down-square-fill" /></template>
