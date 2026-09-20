<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxu8at8bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxu8at8bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:arduino" /></template>
