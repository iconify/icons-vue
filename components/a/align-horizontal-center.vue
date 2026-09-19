<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-l-pb8zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-l-pb8zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:align-horizontal-center" /></template>
