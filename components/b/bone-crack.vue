<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqgu-6_kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wqgu-6_kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bone-crack" /></template>
