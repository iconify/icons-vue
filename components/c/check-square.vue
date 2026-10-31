<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnll1ccis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnll1ccis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:check-square" /></template>
