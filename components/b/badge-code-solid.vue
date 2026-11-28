<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmihy0bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmihy0bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:badge-code-solid" /></template>
