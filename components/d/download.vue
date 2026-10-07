<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpe24tbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpe24tbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:download" /></template>
