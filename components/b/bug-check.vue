<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkv2vgypk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkv2vgypk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bug-check" /></template>
