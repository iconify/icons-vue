<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_xoe9j3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_xoe9j3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-add" /></template>
