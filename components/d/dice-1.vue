<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9d0y6bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9d0y6bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:dice-1" /></template>
