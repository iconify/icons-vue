<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh5fs6bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mh5fs6bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment-check-fill" /></template>
