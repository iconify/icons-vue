<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vedidni9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vedidni9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:circle-20-solid" /></template>
