<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n57ilkbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n57ilkbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-down-circle" /></template>
