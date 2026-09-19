<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-nb9pb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-nb9pb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:gift" /></template>
