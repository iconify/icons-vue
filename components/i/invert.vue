<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf39d-7cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b uf39d-7cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:invert" /></template>
