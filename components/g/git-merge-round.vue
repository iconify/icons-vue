<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y45y97bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y45y97bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-merge-round" /></template>
