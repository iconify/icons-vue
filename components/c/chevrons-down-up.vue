<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbakjhb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbakjhb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chevrons-down-up" /></template>
