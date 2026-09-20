<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amo84csgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amo84csgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bird-fill" /></template>
