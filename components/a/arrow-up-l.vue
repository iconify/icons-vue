<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxkwyfhbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxkwyfhbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:arrow-up-l" /></template>
