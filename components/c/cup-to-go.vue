<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycwxoq74a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycwxoq74a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:cup-to-go" /></template>
