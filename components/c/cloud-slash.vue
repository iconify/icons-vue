<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrpc_ab1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrpc_ab1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-slash" /></template>
