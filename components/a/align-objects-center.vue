<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4_4oj5ld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4_4oj5ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:align-objects-center" /></template>
