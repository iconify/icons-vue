<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l60z0rb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l60z0rb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bts" /></template>
