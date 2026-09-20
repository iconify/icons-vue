<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygez5ob8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygez5ob8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:angle-down-light" /></template>
