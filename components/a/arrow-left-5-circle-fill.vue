<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3_5bzbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k3_5bzbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-left-5-circle-fill" /></template>
