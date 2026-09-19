<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caw1diebi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caw1diebi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:egg" /></template>
