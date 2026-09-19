<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7yn_-5rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7yn_-5rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:electronics-transister" /></template>
