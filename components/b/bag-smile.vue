<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_fdh8bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_fdh8bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bag-smile" /></template>
