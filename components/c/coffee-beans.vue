<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcfen957l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcfen957l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:coffee-beans" /></template>
