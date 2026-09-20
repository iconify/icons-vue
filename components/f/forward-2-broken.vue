<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu604iz0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu604iz0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forward-2-broken" /></template>
