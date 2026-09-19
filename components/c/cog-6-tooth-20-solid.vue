<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h221lkbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h221lkbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cog-6-tooth-20-solid" /></template>
