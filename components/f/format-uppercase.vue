<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf2uan53j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mf2uan53j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:format-uppercase" /></template>
