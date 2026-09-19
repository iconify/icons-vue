<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt6wbbtjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt6wbbtjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chevron-up-small-filled" /></template>
