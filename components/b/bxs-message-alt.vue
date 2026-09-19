<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9gygm7nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9gygm7nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-alt" /></template>
