<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af1ceacli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af1ceacli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-triple-down-solid" /></template>
