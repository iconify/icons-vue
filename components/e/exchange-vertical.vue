<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfrb58b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfrb58b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:exchange-vertical" /></template>
