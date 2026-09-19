<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x21_qv89q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x21_qv89q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ampoule" /></template>
