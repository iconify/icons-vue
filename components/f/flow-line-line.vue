<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhkncj6rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhkncj6rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:flow-line-line" /></template>
