<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2v4d7bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l2v4d7bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:chef-toque-hat-solid" /></template>
