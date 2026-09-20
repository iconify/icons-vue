<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfj16fbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jfj16fbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-vertical-center-outline" /></template>
