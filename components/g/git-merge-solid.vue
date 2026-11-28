<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyup4eb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyup4eb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:git-merge-solid" /></template>
