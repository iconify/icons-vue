<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_xizqv5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_xizqv5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:decagram" /></template>
