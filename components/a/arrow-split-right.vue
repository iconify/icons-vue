<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq_9a7bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eq_9a7bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-split-right" /></template>
