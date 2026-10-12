<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrg2b27ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrg2b27ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:git-pull-request-filled" /></template>
