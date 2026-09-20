<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko7wmu2ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko7wmu2ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:align-center-justify" /></template>
