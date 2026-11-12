<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbc6i7byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbc6i7byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folder-key" /></template>
