<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jizitnexx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jizitnexx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:attachment-outline" /></template>
