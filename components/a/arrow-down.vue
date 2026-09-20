<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otgnvjbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otgnvjbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-down" /></template>
