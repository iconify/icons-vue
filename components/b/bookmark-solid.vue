<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd8rxbb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd8rxbb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:bookmark-solid" /></template>
