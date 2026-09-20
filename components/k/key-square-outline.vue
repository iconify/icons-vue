<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z10jvkbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z10jvkbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-square-outline" /></template>
