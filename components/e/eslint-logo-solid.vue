<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxa7gactv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qxa7gactv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:eslint-logo-solid" /></template>
