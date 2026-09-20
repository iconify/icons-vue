<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0n8kv_ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0n8kv_ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-shell-check-ok" /></template>
