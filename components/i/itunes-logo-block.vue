<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2irf_n0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b2irf_n0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:itunes-logo-block" /></template>
