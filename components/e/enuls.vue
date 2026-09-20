<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7_jx11ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7_jx11ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:enuls" /></template>
