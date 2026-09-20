<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqp9u9b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nqp9u9b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:key-square2" /></template>
