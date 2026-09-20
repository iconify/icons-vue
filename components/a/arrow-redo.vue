<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg5skcb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg5skcb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-redo" /></template>
