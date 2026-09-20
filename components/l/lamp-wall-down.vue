<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzqvqw61x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzqvqw61x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:lamp-wall-down" /></template>
