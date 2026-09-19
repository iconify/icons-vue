<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkz_ggbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkz_ggbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:clipboard" /></template>
