<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggudat3kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggudat3kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-bar" /></template>
