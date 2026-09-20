<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clml3gbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clml3gbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-right" /></template>
