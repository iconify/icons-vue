<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko1unt2th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko1unt2th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:anchor" /></template>
