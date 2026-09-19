<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-ns-1bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-ns-1bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:light-bulb" /></template>
