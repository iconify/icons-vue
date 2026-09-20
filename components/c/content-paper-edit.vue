<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q60ckztmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q60ckztmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:content-paper-edit" /></template>
