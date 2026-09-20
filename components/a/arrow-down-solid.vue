<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d598p2b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d598p2b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-down-solid" /></template>
