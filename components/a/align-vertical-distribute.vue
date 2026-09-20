<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmbk2pjqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmbk2pjqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:align-vertical-distribute" /></template>
