<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brwa9j5pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brwa9j5pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:app-window" /></template>
