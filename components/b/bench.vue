<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvv42hv0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b uvv42hv0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bench" /></template>
