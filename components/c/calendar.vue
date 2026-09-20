<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svmorccoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="svmorccoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:calendar" /></template>
