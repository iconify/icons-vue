<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvf_d7bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xvf_d7bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:ello-logo-block" /></template>
