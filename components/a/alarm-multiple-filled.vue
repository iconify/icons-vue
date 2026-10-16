<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce70qkbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce70qkbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:alarm-multiple-filled" /></template>
