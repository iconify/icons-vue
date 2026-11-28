<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p49y3ab6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p49y3ab6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:comma-solid" /></template>
