<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf7be2b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf7be2b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flask-empty-plus" /></template>
