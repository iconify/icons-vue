<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv5q_8bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv5q_8bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:behance" /></template>
