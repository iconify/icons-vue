<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6aym8bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6aym8bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:amazoncognito" /></template>
