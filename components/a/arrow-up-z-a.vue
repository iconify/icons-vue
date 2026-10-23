<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyjc752ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyjc752ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-z-a" /></template>
