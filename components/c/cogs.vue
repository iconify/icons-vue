<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b89_mpbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1792};
const content = `<path class="b89_mpbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cogs" /></template>
