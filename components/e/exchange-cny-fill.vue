<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk7nj-bqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk7nj-bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exchange-cny-fill" /></template>
