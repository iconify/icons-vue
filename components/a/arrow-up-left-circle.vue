<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq9pkcaia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq9pkcaia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-up-left-circle" /></template>
