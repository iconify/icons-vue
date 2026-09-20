<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npa5ly1qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npa5ly1qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-bunpo" /></template>
