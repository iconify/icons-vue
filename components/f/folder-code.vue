<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqe5ph00n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqe5ph00n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folder-code" /></template>
