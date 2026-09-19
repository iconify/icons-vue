<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dax7uhcrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dax7uhcrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:downvote" /></template>
