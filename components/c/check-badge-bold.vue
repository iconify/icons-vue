<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcdvrtlrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcdvrtlrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:check-badge-bold" /></template>
