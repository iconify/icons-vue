<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyikxh0ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pyikxh0ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:key-outline" /></template>
