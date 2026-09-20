<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3k8_56mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3k8_56mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-v-small" /></template>
