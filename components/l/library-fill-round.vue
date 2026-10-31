<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwwb8k8on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwwb8k8on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:library-fill-round" /></template>
