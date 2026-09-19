<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd4oa2b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd4oa2b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:check-outline" /></template>
