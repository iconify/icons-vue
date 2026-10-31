<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn91b5qub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn91b5qub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:carrot-fill-round" /></template>
