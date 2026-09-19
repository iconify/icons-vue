<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dskthnbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dskthnbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:film-roll-filled" /></template>
