<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/typj2ptvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="typj2ptvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-a-small" /></template>
