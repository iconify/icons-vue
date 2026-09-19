<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chv7bmbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chv7bmbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:badge-plus" /></template>
