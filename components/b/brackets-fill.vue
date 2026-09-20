<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjxtmvqzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjxtmvqzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brackets-fill" /></template>
