<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtc9d7bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtc9d7bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:leo" /></template>
