<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbru06b6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbru06b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-chevron-left-fill" /></template>
