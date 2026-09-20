<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9voh_k8p.css';
import '../../css/u/uv6e99bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9voh_k8p"/><path class="uv6e99bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:laptop-help-message-bold" /></template>
