<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfz1s_bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfz1s_bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bulb" /></template>
