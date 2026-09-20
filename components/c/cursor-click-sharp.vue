<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly1huxb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly1huxb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-click-sharp" /></template>
