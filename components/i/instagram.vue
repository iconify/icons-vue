<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_0ldelps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_0ldelps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:instagram" /></template>
