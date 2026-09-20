<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh5w3rbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh5w3rbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-loop-outline" /></template>
