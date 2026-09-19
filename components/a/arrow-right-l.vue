<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn-s6sfow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn-s6sfow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:arrow-right-l" /></template>
