<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko1__nbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko1__nbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bold-duotone" /></template>
