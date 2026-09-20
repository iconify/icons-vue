<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1gne2q2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1gne2q2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:divide-outline" /></template>
