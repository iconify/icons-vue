<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdga42b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdga42b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-loop" /></template>
