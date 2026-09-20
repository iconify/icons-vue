<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfw__5bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfw__5bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-up-wide-line" /></template>
