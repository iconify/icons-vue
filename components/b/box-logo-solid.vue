<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbyun6njj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kbyun6njj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:box-logo-solid" /></template>
