<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbv_7acjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbv_7acjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-up-3" /></template>
