<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf7f2ebgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf7f2ebgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:info-square-outline" /></template>
