<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnw1lqbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnw1lqbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:gift" /></template>
