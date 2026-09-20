<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mya2ylbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mya2ylbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrows-up" /></template>
