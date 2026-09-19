<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unnj-gbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unnj-gbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:heart-add" /></template>
