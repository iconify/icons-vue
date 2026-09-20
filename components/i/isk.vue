<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn8q6fsbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn8q6fsbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:isk" /></template>
