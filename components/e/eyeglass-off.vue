<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfxbv640g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfxbv640g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:eyeglass-off" /></template>
