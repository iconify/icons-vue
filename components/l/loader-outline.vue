<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1j-u4bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1j-u4bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:loader-outline" /></template>
