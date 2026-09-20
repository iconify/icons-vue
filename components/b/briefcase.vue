<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yji5pzqcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yji5pzqcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:briefcase" /></template>
